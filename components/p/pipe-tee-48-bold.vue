<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7znocbrd.css';
import '../../css/e/e2r4n70kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z7znocbrd"/><path class="e2r4n70kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-tee-48-bold" /></template>
