<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t1ivbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2t1ivbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:quora" /></template>
