<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaaps2u-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaaps2u-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webdriverio" /></template>
