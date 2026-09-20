<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnop94bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnop94bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:zip" /></template>
