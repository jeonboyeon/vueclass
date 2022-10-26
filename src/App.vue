<template>
    <div>
        <HeaderLayout fonts="nexon" />
        <SliderSection />
        <ImageSection attr="section nexon target" layout="image__inner container" />
        <ImageTextSection attr="section nexon gray target" layout="imgText__inner container" />
        <CardSection attr="section nexon target" layout="card__inner container" />
        <BannerSection attr="nexon target" layout="banner__inner" />
        <TextSection attr="section nexon target" layout="text__inner container" />
        <FooterLayout attr="section nexon gray" layout="text__inner" />
    </div>
</template>

<script>
import FooterLayout from "./components/layout/FooterLayout.vue";
import HeaderLayout from "./components/layout/HeaderLayout.vue";
import SliderSection from "./components/section/SliderSection.vue";
import ImageSection from "./components/section/ImageSection.vue";
import ImageTextSection from "./components/section/ImageTextSection.vue";
import CardSection from "./components/section/CardSection.vue";
import BannerSection from "./components/section/BannerSection.vue";
import TextSection from "./components/section/TextSection.vue";

export default {
    name: "App",
    components: {
        HeaderLayout,
        SliderSection,
        ImageSection,
        ImageTextSection,
        CardSection,
        BannerSection,
        TextSection,
        FooterLayout
    }
};
</script>

<style>
</style>
