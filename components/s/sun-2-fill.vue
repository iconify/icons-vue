<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at_1occme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at_1occme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-2-fill" /></template>
