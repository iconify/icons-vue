<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff6e6iscy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff6e6iscy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ranking3" /></template>
