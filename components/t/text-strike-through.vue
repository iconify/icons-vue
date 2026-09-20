<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n072rrlng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n072rrlng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-strike-through" /></template>
