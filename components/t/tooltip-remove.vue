<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j37ymlt7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j37ymlt7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-remove" /></template>
