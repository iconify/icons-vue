<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4o6ss61z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4o6ss61z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:paragraph" /></template>
