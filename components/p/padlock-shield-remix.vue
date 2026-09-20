<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr4rj9b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr4rj9b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:padlock-shield-remix" /></template>
