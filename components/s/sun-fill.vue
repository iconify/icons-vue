<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drgj63bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drgj63bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-fill" /></template>
