<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9mmi8b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9mmi8b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stroke-line-join-miter" /></template>
