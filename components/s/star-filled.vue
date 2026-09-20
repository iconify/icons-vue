<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvtkrww7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvtkrww7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-filled" /></template>
