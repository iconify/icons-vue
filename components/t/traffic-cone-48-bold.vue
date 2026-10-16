<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe1o59byh.css';
import '../../css/a/anawxhbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pe1o59byh"/><path class="anawxhbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-cone-48-bold" /></template>
