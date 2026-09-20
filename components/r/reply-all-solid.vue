<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixwu8vpus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixwu8vpus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:reply-all-solid" /></template>
