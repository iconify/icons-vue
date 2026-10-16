<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyo6-384c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cyo6-384c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-landing-20" /></template>
