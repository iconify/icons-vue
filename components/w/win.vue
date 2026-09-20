<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaw9wkbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw9wkbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:win" /></template>
