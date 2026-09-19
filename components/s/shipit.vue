<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq7dhvbqx.css';
import '../../css/p/pf1wtprxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tq7dhvbqx"/><path class="pf1wtprxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:shipit" /></template>
