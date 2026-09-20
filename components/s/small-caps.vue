<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si9wz7b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="si9wz7b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:small-caps" /></template>
