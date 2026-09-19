<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0_165kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw0_165kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:poop" /></template>
