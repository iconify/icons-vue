<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dht-4qb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dht-4qb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:volume" /></template>
