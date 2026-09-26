<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v75x9gbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v75x9gbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-outline" /></template>
