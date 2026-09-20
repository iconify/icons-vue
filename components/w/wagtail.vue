<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8bw__biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8bw__biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wagtail" /></template>
