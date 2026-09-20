<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ike6rfddh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ike6rfddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:scania" /></template>
