<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkyvqobmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bkyvqobmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:timer-zero-remix" /></template>
