<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu00t77rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iu00t77rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:passport-bold" /></template>
