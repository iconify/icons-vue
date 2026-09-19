<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jat4aubqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jat4aubqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sort-numeric-up" /></template>
