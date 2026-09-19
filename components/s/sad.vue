<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcn-pab0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rcn-pab0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sad" /></template>
