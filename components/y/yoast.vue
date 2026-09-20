<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9_w5jbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y9_w5jbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yoast" /></template>
