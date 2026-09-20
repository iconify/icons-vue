<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itzhgkb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itzhgkb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:text" /></template>
