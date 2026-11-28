<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb5b-i9ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb5b-i9ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-arrow-right-solid" /></template>
