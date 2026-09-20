<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s606sacjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s606sacjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sharp" /></template>
