<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no8etixlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no8etixlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:warning" /></template>
