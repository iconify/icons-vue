<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr3umgb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr3umgb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minimize-square" /></template>
