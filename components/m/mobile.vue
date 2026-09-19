<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8zpob_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8zpob_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:mobile" /></template>
