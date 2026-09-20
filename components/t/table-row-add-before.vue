<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcpllflzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcpllflzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-row-add-before" /></template>
