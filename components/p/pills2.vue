<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etr2pwbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="etr2pwbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pills2" /></template>
