<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9inqtbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="z9inqtbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:pagelines" /></template>
