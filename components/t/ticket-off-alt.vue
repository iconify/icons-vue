<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inc-f_bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inc-f_bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ticket-off-alt" /></template>
