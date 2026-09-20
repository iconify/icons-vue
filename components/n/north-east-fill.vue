<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4p0i5b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4p0i5b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-fill" /></template>
