<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bt50oi7lt.css';
import '../../css/k/kmdeqz87h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bt50oi7lt"/><path clip-rule="evenodd" class="kmdeqz87h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:rightwards-hand-medium-dark" /></template>
