<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb0l2eb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pb0l2eb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pen-nib-solid" /></template>
