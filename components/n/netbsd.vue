<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arncd_89v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arncd_89v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:netbsd" /></template>
