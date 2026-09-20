<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytd48tbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ytd48tbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sharing-data-solid" /></template>
