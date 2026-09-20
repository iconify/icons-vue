<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3mtlhbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3mtlhbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-underline-filled" /></template>
