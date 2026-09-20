<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l58myqbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l58myqbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-rewind-fill" /></template>
