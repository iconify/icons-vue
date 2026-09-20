<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0e4rvtar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0e4rvtar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrestling" /></template>
