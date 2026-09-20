<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le0i-4b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le0i-4b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:paperclip-2-flat" /></template>
