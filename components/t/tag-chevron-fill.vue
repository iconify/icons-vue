<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpxwfh1kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpxwfh1kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-chevron-fill" /></template>
