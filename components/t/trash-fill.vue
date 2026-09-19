<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo6z1ibjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bo6z1ibjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-fill" /></template>
