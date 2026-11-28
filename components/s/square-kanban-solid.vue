<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujhvyhjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xujhvyhjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-kanban-solid" /></template>
