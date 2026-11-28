<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3qemvq9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3qemvq9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:panel-bottom-collapse-solid" /></template>
