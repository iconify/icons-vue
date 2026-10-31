<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm-kqz9jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm-kqz9jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spell-check-round" /></template>
