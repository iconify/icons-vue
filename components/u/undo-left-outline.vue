<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqdxw7bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqdxw7bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-outline" /></template>
