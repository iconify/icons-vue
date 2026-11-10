<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp1ojc_zq.css';
import '../../css/n/nucjxzbql.css';
import '../../css/u/uz5m12bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tp1ojc_zq"/><path class="nucjxzbql"/><path class="uz5m12bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nginx-wordmark" /></template>
