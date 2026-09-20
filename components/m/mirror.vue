<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjf6_87ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjf6_87ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror" /></template>
