<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pghnx8bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pghnx8bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mirror" /></template>
