<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruhwp_-bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruhwp_-bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:medium-m" /></template>
