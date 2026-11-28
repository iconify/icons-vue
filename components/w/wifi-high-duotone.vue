<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6zafjb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6zafjb8i primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wifi-high-duotone" /></template>
