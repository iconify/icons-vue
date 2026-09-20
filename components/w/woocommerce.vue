<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiub_ndwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiub_ndwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:woocommerce" /></template>
