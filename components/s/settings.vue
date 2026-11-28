<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk3ftabft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk3ftabft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:settings" /></template>
