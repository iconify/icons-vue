<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob-lpacex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob-lpacex primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:signal-medium-duotone" /></template>
