<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxjl0ubfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxjl0ubfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-left-dashed-filled" /></template>
