<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0ctrg0qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0ctrg0qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:move-file-remix" /></template>
