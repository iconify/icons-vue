<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqm7syblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqm7syblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-root-solid" /></template>
