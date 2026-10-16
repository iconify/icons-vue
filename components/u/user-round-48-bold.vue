<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moyoz5fkv.css';
import '../../css/p/p5ne8n6_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="p5ne8n6_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-round-48-bold" /></template>
