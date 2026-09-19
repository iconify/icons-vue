<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7m2xbxv.css';
import '../../css/v/v999jcc3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lu7m2xbxv"/><path class="v999jcc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torsos-all" /></template>
