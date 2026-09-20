<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhw-h4bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhw-h4bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:party-popper-remix" /></template>
