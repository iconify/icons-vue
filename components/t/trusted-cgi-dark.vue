<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9qpevy0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9qpevy0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trusted-cgi-dark" /></template>
