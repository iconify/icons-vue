<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn0n3pbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn0n3pbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-6-solid" /></template>
