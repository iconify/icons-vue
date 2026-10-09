<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aopgjf_lo.css';
import '../../css/f/f-1ndobgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aopgjf_lo"/><path class="f-1ndobgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:note-20-bold" /></template>
