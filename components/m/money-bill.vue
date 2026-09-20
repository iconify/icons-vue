<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4mym1_0y.css';
import '../../css/l/ln6rcys8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4mym1_0y"/><path class="ln6rcys8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:money-bill" /></template>
