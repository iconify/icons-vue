<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdfa4_f-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdfa4_f-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:photograph" /></template>
