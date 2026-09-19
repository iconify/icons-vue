<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfab8ibes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfab8ibes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:print" /></template>
