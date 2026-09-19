<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<polygon points="8 1.75 5.75 5.75 1.75 6.25 4.75 9.75 3.75 14.25 8 12.25 12.25 14.25 11.25 9.75 14.25 6.25 10.25 5.75" class="hntgybcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:star" /></template>
