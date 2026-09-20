<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhroet0on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhroet0on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-2" /></template>
