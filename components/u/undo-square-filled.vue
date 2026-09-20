<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_u1qfr8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_u1qfr8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:undo-square-filled" /></template>
