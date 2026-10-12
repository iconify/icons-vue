<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8md41vjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8md41vjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paint-bucket-filled" /></template>
