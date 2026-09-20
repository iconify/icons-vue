<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_eh8bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rv_eh8bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tower-5-fill" /></template>
