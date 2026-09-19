<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugrnpeb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ugrnpeb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-web-awesome-stroke" /></template>
