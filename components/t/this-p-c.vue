<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6rtqrp3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d6rtqrp3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:this-p-c" /></template>
