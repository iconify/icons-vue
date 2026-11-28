<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqs_i4b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqs_i4b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:markdown-solid" /></template>
