<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6k55bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt6k55bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:snapchat-ghost" /></template>
