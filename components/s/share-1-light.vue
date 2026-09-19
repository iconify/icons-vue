<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzw3f80ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzw3f80ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-1-light" /></template>
