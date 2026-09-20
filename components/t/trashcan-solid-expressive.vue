<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrdu5lrsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrdu5lrsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:trashcan-solid-expressive" /></template>
