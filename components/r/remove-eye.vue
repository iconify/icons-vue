<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih95x1b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ih95x1b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:remove-eye" /></template>
