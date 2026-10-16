<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c93ue0bjc.css';
import '../../css/c/c47fazbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c93ue0bjc"/><path class="c47fazbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ratchet-20-bold" /></template>
