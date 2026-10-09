<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeaj4ri2b.css';
import '../../css/x/xn9gzsb0y.css';
import '../../css/h/hlj3itbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zeaj4ri2b"/><path class="xn9gzsb0y"/><path class="hlj3itbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yoga-48" /></template>
