<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apzc8db8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apzc8db8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-black-hexagons" /></template>
