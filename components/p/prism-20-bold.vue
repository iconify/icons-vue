<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbmfgacnw.css';
import '../../css/d/d90ivtb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wbmfgacnw"/><path class="d90ivtb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:prism-20-bold" /></template>
