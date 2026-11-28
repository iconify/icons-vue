<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tldz3lrhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tldz3lrhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:train" /></template>
