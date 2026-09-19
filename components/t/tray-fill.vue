<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycf3u1r9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ycf3u1r9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-fill" /></template>
