<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpkq7ob1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpkq7ob1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-arrow-left-filled" /></template>
