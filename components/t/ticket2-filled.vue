<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zthcrwb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zthcrwb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket2-filled" /></template>
