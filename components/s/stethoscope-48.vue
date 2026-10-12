<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0k1v4bte.css';
import '../../css/l/lwiyvud8h.css';
import '../../css/d/dv82jtb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0k1v4bte"/><path class="lwiyvud8h"/><path class="dv82jtb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stethoscope-48" /></template>
