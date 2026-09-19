<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cirm-9b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cirm-9b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:question-triangle-24px" /></template>
