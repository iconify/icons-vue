<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyja5evvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyja5evvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:won" /></template>
