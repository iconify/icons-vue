<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h28-skbwv.css';
import '../../css/b/b7rjdgn0s.css';
import '../../css/l/ly00bcc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h28-skbwv"/><path class="b7rjdgn0s"/><path class="ly00bcc9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:node-remove" /></template>
