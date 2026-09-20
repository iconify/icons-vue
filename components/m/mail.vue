<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p84b_2b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p84b_2b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:mail" /></template>
