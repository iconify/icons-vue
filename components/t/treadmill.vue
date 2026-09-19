<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6e4blykc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6e4blykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:treadmill" /></template>
