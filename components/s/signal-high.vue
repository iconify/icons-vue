<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2qebubli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2qebubli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signal-high" /></template>
