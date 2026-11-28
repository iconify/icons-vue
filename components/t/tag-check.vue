<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbkca8bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbkca8bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tag-check" /></template>
