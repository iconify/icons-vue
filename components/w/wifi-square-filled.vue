<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9zx36l4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9zx36l4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wifi-square-filled" /></template>
