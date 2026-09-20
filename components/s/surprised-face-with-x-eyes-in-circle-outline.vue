<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzdcx9bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bzdcx9bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:surprised-face-with-x-eyes-in-circle-outline" /></template>
