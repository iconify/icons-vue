<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7no_4brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7no_4brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-bold" /></template>
