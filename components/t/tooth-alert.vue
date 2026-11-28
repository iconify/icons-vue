<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmvdr_n-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmvdr_n-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tooth-alert" /></template>
