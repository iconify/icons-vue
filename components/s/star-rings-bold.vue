<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebywk9ozr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebywk9ozr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-bold" /></template>
