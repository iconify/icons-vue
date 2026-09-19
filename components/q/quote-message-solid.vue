<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf7qo0fud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf7qo0fud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:quote-message-solid" /></template>
