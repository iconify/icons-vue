<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6sb9-bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6sb9-bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:move-fill" /></template>
