<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux53b_6so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ux53b_6so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:smiley-drool-solid" /></template>
