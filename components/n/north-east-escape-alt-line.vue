<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntjvn0hrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntjvn0hrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-escape-alt-line" /></template>
