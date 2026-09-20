<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az8eyjsjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az8eyjsjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:path-filled" /></template>
