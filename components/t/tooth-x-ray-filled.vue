<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb7iodb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bb7iodb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-x-ray-filled" /></template>
