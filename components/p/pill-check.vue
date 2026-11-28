<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-p5v55ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-p5v55ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pill-check" /></template>
