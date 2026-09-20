<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqn6dznwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqn6dznwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-ascending" /></template>
