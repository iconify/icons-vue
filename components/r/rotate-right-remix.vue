<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx80lq-0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fx80lq-0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rotate-right-remix" /></template>
