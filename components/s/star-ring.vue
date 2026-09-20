<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b65-p4bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b65-p4bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-ring" /></template>
