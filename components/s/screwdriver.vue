<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw4fqzb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jw4fqzb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:screwdriver" /></template>
