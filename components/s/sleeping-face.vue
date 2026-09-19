<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmuh98bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gmuh98bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:sleeping-face" /></template>
