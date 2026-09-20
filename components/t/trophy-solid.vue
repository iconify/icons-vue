<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/steyh-bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="steyh-bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:trophy-solid" /></template>
