<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<polygon points="5.25 1.75 10.75 1.75 14.25 5.25 14.25 10.75 10.75 14.25 5.25 14.25 1.75 10.75 1.75 5.25" class="hntgybcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:octagon" /></template>
