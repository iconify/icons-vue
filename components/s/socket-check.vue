<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4d-6lb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4d-6lb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:socket-check" /></template>
