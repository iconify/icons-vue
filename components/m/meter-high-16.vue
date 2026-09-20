<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oewliqb1a.css';
import '../../css/c/cc1vgdb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oewliqb1a"/><path class="cc1vgdb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:meter-high-16" /></template>
