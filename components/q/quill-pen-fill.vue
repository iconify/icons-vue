<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdu937bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdu937bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quill-pen-fill" /></template>
