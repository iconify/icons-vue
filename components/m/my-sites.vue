<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaferwb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaferwb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:my-sites" /></template>
