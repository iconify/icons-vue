<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq1gg58db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="yq1gg58db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:telegram" /></template>
