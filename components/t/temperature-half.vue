<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku-h9g-aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku-h9g-aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:temperature-half" /></template>
