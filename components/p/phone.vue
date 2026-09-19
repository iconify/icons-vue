<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmsy4ybos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmsy4ybos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone" /></template>
