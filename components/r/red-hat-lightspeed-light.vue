<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxwu6fq3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxwu6fq3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat-lightspeed-light" /></template>
