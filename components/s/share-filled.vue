<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cavg_bvbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cavg_bvbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:share-filled" /></template>
