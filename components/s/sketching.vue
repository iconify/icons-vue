<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qov0oub3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qov0oub3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sketching" /></template>
