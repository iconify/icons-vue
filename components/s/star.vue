<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-f7f-_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id-f7f-_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:star" /></template>
