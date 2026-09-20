<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6nf6mb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6nf6mb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:messages-logo-solid" /></template>
