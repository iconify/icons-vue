<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iua_9vstk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iua_9vstk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:squares-2x2" /></template>
