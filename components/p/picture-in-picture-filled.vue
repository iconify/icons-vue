<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm1hi_b-d.css';
import '../../css/f/ffq0z92oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm1hi_b-d"/><path class="ffq0z92oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:picture-in-picture-filled" /></template>
