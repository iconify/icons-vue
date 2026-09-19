<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb79k96ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="kb79k96ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:microphone-alt-slash" /></template>
