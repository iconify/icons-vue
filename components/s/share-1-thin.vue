<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvom3bcqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvom3bcqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-1-thin" /></template>
