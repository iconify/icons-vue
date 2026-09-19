<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyerzhc-f.css';
import '../../css/t/t6lf1fb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iyerzhc-f"/><path class="t6lf1fb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:reading-lamp" /></template>
