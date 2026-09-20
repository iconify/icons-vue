<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_c3p21ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_c3p21ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:no-pets-allowed-remix" /></template>
