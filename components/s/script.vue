<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olf29kb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olf29kb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:script" /></template>
