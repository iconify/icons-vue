<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4tpoeb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4tpoeb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:tea-sharp" /></template>
