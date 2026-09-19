<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndvb1fb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndvb1fb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-x-ray" /></template>
