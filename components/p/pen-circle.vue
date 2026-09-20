<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ac8zb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0ac8zb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-circle" /></template>
