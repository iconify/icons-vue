<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d55zawbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d55zawbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:receive-euros" /></template>
