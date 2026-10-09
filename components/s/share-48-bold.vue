<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob6rb5b4d.css';
import '../../css/g/g620y8-kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ob6rb5b4d"/><path class="g620y8-kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-48-bold" /></template>
