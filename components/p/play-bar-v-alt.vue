<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8fv5cbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8fv5cbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-v-alt" /></template>
