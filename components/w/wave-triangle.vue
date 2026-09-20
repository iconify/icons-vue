<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylpqp1b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylpqp1b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:wave-triangle" /></template>
