<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j93dpcc-p.css';
import '../../css/t/tw_o15b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j93dpcc-p"/><path class="tw_o15b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-unread-20-bold" /></template>
