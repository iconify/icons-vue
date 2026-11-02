<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tog098bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tog098bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sweats-fill" /></template>
