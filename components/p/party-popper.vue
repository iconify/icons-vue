<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1o8w7iar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1o8w7iar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:party-popper" /></template>
