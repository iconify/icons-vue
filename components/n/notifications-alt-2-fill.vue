<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ful9cebla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ful9cebla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-alt-2-fill" /></template>
