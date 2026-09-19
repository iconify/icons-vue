<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faxk6dnrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faxk6dnrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:users" /></template>
