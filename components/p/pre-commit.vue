<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik2aijy3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik2aijy3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pre-commit" /></template>
