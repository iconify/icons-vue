<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbf205b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbf205b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:twitter" /></template>
