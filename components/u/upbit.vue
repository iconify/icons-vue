<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3xlpbb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3xlpbb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:upbit" /></template>
