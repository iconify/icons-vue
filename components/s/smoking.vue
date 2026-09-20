<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3_5w4bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c3_5w4bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:smoking" /></template>
