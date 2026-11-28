<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1xfj5k7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary r1xfj5k7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-cursor-duotone" /></template>
