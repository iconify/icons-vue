<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojad3gbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojad3gbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:trello-logo-solid" /></template>
