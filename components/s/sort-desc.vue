<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb918ob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb918ob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-desc" /></template>
