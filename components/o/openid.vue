<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4w_gbbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="g4w_gbbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:openid" /></template>
