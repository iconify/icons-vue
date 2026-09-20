<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffevzz76e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffevzz76e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:texture" /></template>
