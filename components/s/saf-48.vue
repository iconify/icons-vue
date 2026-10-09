<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edwtppbpi.css';
import '../../css/a/aw5_q9beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="edwtppbpi"/><path class="aw5_q9beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saf-48" /></template>
