<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzh2qt3br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh2qt3br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:menu" /></template>
