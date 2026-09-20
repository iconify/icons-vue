<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj2ms3n-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rj2ms3n-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:phone-actions-merge" /></template>
