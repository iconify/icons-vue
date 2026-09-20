<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_hap2nuf.css';
import '../../css/e/ee_cdkb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_hap2nuf"/><path clip-rule="evenodd" class="ee_cdkb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:run-debug-16" /></template>
