<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwvkl-j3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwvkl-j3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-check-solid" /></template>
