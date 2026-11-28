<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfjdu5a6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfjdu5a6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-plus-solid" /></template>
