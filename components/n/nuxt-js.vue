<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttwf1n2vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ttwf1n2vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nuxt-js" /></template>
