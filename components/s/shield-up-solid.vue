<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk0fb3byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk0fb3byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-up-solid" /></template>
