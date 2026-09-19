<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr00jacgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dr00jacgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-cancel-filled" /></template>
