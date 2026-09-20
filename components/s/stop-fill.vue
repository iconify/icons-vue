<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsodg2gky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsodg2gky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stop-fill" /></template>
