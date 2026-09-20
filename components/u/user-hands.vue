<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up4rrqezu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up4rrqezu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-hands" /></template>
