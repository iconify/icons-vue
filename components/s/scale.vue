<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty380eb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty380eb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scale" /></template>
