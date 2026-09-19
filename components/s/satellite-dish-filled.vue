<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okqm3vb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okqm3vb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:satellite-dish-filled" /></template>
