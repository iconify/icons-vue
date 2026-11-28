<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pikr_rilf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pikr_rilf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-check-solid" /></template>
