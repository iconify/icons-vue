<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/batmvgb8l.css';
import '../../css/k/ks20pegmu.css';
import '../../css/d/dczvvtbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="batmvgb8l"/><path class="ks20pegmu"/><path class="dczvvtbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speaker-48" /></template>
