<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptvnpwuto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptvnpwuto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vidicon-line" /></template>
