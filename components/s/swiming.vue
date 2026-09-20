<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m912t5v7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m912t5v7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swiming" /></template>
