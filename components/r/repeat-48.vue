<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x13lcabyi.css';
import '../../css/o/oi3fybc0n.css';
import '../../css/w/w9t884b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x13lcabyi"/><path class="oi3fybc0n"/><path class="w9t884b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-48" /></template>
