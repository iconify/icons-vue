<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6o5_008e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6o5_008e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stove" /></template>
