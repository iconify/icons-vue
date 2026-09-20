<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu5zp6fme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu5zp6fme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tooltip" /></template>
