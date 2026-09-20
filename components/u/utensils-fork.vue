<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abqzle30w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abqzle30w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:utensils-fork" /></template>
