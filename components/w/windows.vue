<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz-v30kpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qz-v30kpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:windows" /></template>
