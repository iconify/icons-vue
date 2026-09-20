<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny_6rsfhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny_6rsfhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xbox-live-logo-solid" /></template>
