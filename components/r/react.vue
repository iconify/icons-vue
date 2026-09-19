<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v1z1bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4v1z1bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:react" /></template>
