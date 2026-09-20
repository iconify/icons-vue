<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghzw70bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ghzw70bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:won-sign-solid" /></template>
