<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twg3zq-7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twg3zq-7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:running" /></template>
