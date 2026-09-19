<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knk5ty9ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knk5ty9ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stairs-04" /></template>
