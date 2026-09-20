<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9yyi5bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9yyi5bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shirt" /></template>
