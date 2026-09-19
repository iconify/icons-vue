<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o612d83qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o612d83qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:surfboard" /></template>
