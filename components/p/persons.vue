<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo6q0qbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="xo6q0qbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:persons" /></template>
