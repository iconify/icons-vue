<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgth8dbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgth8dbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:radio-remix" /></template>
