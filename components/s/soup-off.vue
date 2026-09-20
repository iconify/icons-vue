<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_tn-8b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_tn-8b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:soup-off" /></template>
