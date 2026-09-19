<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/benc_65rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":426,"height":768};
const content = `<path class="benc_65rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:pin" /></template>
