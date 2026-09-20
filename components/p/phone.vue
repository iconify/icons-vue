<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-b21jb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-b21jb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:phone" /></template>
