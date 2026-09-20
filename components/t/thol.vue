<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6k0tsmzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h6k0tsmzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:thol" /></template>
