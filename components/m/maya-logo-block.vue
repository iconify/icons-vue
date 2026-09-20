<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h27hywb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h27hywb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:maya-logo-block" /></template>
