<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-nwl6b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-nwl6b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-x" /></template>
