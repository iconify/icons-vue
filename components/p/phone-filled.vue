<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zitu69bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zitu69bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:phone-filled" /></template>
