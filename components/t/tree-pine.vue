<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay53_oboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay53_oboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tree-pine" /></template>
