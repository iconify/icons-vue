<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy07pqbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy07pqbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-percent-solid" /></template>
