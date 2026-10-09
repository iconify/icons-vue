<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6cvwtbsp.css';
import '../../css/r/r4a32cb3q.css';
import '../../css/r/raz-mzj-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="r4a32cb3q"/><path class="raz-mzj-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-habitat-48-bold" /></template>
