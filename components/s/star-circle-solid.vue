<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo6xbn6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfo6xbn6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:star-circle-solid" /></template>
