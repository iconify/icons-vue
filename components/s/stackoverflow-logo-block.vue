<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_alj1b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_alj1b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stackoverflow-logo-block" /></template>
