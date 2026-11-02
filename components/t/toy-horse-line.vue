<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7mjcxbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7mjcxbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toy-horse-line" /></template>
