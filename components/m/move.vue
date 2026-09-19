<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s59g9_0ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s59g9_0ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:move" /></template>
