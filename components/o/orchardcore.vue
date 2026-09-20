<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe170yvls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe170yvls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:orchardcore" /></template>
