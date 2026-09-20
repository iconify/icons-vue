<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss89lq90u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ss89lq90u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:target" /></template>
