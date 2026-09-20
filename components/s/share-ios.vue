<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5n8ghm7o.css';
import '../../css/w/wq_f_lb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s5n8ghm7o"/><path class="wq_f_lb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:share-ios" /></template>
