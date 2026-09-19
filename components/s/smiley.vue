<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-8gtcm1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y-8gtcm1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:smiley" /></template>
