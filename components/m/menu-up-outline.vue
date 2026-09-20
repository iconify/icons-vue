<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tupdf321f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tupdf321f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-up-outline" /></template>
