<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e658-774s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="e658-774s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:roundswitch-on" /></template>
