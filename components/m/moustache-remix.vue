<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl6b8fzab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl6b8fzab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:moustache-remix" /></template>
