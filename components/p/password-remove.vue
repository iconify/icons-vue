<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahiw1-bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahiw1-bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:password-remove" /></template>
