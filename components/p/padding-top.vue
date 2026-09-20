<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e727a1bty.css';
import '../../css/r/r98qut7eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e727a1bty"/><path class="r98qut7eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:padding-top" /></template>
