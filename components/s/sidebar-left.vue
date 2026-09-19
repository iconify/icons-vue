<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd--g6b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fd--g6b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sidebar-left" /></template>
