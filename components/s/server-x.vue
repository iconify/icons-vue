<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5f_9mbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5f_9mbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:server-x" /></template>
