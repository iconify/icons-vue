<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usy2kj38d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usy2kj38d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search2" /></template>
