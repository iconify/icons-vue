<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eopkqoboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eopkqoboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-work-laptop-wifi-solid" /></template>
