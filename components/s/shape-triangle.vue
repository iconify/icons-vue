<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrfc46b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrfc46b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:shape-triangle" /></template>
