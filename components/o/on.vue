<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v19gj253m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v19gj253m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:on" /></template>
