<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9jn-l41s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9jn-l41s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-right-filled" /></template>
