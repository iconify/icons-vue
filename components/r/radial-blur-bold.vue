<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uak_0hbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uak_0hbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radial-blur-bold" /></template>
