<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdh-3kkjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdh-3kkjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ticket-fill" /></template>
