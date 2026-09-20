<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0jn-wb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0jn-wb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zee" /></template>
