<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg9h9d2-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg9h9d2-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tablets-solid" /></template>
