<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n23pribvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n23pribvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-outline" /></template>
