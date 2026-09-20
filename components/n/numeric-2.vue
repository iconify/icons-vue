<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9r3hpbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9r3hpbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-2" /></template>
