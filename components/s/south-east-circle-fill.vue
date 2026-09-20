<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7x8w6hli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7x8w6hli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-east-circle-fill" /></template>
