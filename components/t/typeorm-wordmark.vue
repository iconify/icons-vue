<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppt0_abcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ppt0_abcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typeorm-wordmark" /></template>
