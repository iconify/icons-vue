<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1j_mjb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1j_mjb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-fill" /></template>
