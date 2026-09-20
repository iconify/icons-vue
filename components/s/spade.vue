<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4p6gw4td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4p6gw4td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:spade" /></template>
