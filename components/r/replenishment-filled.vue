<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3c_gcb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f3c_gcb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:replenishment-filled" /></template>
