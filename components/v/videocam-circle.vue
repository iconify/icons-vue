<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-6w0qb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="n-6w0qb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:videocam-circle" /></template>
