<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8rfl0h4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8rfl0h4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nebula" /></template>
