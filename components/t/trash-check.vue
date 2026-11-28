<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzsr340v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwzsr340v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:trash-check" /></template>
