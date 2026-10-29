<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhqjqqb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhqjqqb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:share" /></template>
