<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35zbv-id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f35zbv-id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:radial-rays-solid" /></template>
