<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owg7w8ayy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owg7w8ayy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:smart" /></template>
