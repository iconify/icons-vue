<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usac0up9h.css';
import '../../css/b/bo0bdiq0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="usac0up9h"/><path class="bo0bdiq0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:power" /></template>
