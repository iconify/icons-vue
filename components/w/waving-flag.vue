<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj_1dobai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sj_1dobai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:waving-flag" /></template>
