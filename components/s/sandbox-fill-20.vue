<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig-lqcc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ig-lqcc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sandbox-fill-20" /></template>
