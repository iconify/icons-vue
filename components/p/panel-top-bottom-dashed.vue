<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v06u48b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v06u48b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-top-bottom-dashed" /></template>
