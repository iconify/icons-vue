<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kepg9yfyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kepg9yfyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:thumbs-down" /></template>
