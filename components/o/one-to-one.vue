<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf6dffx8p.css';
import '../../css/g/gc8-4tb2b.css';
import '../../css/n/n7u8j-8_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kf6dffx8p"/><path class="gc8-4tb2b"/><path class="n7u8j-8_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:one-to-one" /></template>
