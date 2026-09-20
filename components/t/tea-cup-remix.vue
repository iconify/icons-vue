<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp4ir1wnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp4ir1wnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tea-cup-remix" /></template>
