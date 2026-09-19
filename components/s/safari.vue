<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik0_kn2ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ik0_kn2ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:safari" /></template>
