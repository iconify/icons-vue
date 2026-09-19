<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2nh5t9ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2nh5t9ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sql" /></template>
