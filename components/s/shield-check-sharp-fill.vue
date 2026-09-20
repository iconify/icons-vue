<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2-48nb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2-48nb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-check-sharp-fill" /></template>
