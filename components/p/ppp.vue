<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_xvs-ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v3_xvs-ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ppp" /></template>
