<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq2503bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq2503bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-l" /></template>
