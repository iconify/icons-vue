<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f04w38lpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f04w38lpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stop-light" /></template>
