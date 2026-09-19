<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrea60bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrea60bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:share-social-sharp" /></template>
