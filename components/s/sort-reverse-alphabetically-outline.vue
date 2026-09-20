<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/surswrb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="surswrb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-reverse-alphabetically-outline" /></template>
