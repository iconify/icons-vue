<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kktn4_nwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="kktn4_nwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:share-5" /></template>
