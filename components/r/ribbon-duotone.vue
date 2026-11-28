<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6b6ryozd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v6b6ryozd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ribbon-duotone" /></template>
