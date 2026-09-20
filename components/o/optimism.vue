<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz2-91bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dz2-91bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:optimism" /></template>
