<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5igb5bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p5igb5bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-temporary-ltr" /></template>
