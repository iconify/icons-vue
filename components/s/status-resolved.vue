<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4v017l6t.css';
import '../../css/v/v1j9wac_l.css';
import '../../css/s/sy9gb5bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l4v017l6t"/><path class="v1j9wac_l"/><path class="sy9gb5bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:status-resolved" /></template>
