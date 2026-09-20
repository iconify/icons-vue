<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg_1ndbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rg_1ndbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunset-fill" /></template>
