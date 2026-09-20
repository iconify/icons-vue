<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p987tibhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p987tibhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-none-remix" /></template>
