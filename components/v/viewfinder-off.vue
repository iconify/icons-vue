<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg8r7mbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg8r7mbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:viewfinder-off" /></template>
