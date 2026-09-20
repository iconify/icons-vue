<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwnuw_b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwnuw_b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:open-umbrella-remix" /></template>
