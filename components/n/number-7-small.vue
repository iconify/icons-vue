<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr5t35m0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr5t35m0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-7-small" /></template>
