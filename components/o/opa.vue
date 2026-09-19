<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd7ji-5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qd7ji-5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:opa" /></template>
