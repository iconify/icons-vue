<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r67kl8-5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r67kl8-5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ticket" /></template>
