<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnqy7hb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnqy7hb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:multiply" /></template>
