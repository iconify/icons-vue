<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl-22xbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sl-22xbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mask-solid" /></template>
