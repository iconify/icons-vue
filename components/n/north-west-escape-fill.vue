<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r67n7p6du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r67n7p6du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-escape-fill" /></template>
