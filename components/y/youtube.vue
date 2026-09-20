<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti2uwrbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti2uwrbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:youtube" /></template>
