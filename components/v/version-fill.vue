<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6q-x2b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6q-x2b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:version-fill" /></template>
