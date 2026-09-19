<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh95zyn8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oh95zyn8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:youtube-solid" /></template>
