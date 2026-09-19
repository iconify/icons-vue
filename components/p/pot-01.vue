<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r82pb0bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r82pb0bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pot-01" /></template>
