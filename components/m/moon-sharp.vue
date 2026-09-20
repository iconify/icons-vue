<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzqpya2xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzqpya2xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-sharp" /></template>
