<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hknrkvh-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hknrkvh-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler4-filled" /></template>
