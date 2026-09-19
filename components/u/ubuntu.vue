<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8s28ac3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="w8s28ac3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:ubuntu" /></template>
