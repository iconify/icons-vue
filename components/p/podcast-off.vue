<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwqi8rwxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqi8rwxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast-off" /></template>
