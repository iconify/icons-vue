<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9j-avfui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9j-avfui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-bug-outline" /></template>
