<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjm_-zaob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjm_-zaob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:webstorm" /></template>
