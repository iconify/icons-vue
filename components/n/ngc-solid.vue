<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izkbg5b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="izkbg5b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ngc-solid" /></template>
