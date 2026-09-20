<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y69tapb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y69tapb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-alert-fill" /></template>
