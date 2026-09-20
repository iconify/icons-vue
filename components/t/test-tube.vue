<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh8car4ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh8car4ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:test-tube" /></template>
