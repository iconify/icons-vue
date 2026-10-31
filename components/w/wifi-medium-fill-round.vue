<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8o6k5bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8o6k5bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-medium-fill-round" /></template>
