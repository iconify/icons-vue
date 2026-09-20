<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igen-tb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igen-tb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:replay-filled" /></template>
