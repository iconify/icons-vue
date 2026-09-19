<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvdr71a1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvdr71a1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:search-check" /></template>
