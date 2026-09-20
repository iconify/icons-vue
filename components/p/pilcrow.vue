<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0fbj7bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="x0fbj7bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pilcrow" /></template>
