<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mguys6byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mguys6byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-left2" /></template>
