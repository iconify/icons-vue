<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azt6sbb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azt6sbb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:numbered-list" /></template>
