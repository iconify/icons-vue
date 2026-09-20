<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvrkuccoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yvrkuccoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:twitter" /></template>
