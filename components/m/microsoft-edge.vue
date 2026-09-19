<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laswyacqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="laswyacqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:microsoft-edge" /></template>
