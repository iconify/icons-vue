<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9qmy2bro.css';
import '../../css/x/xbe1ae31o.css';
import '../../css/o/o0b52w97m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o9qmy2bro"/><path class="xbe1ae31o"/><path class="o0b52w97m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wand-48" /></template>
