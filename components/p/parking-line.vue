<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v95e19b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95e19b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-line" /></template>
