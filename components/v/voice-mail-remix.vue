<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v98sy1bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v98sy1bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:voice-mail-remix" /></template>
