<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyjii7bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyjii7bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:volume-off" /></template>
