<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbngqvb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbngqvb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:minus-square-solid" /></template>
