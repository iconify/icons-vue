<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn_s5h0rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fn_s5h0rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:weight-scale" /></template>
