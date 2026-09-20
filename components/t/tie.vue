<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c422gb8zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c422gb8zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tie" /></template>
