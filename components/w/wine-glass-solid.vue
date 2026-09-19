<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vodhtj5bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vodhtj5bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:wine-glass-solid" /></template>
