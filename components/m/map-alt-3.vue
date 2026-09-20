<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoduyz_9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uoduyz_9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:map-alt-3" /></template>
