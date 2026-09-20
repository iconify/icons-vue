<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbk3j_dhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbk3j_dhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-time-remix" /></template>
