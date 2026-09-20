<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpb2fcc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpb2fcc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:multiselect-fill" /></template>
