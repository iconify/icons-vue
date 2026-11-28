<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnie1semd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnie1semd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:router" /></template>
