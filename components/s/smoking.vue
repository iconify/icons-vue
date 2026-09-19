<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wczi_xsit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wczi_xsit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:smoking" /></template>
