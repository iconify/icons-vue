<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq6yi9hgq.css';
import '../../css/i/icz8l1jmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vq6yi9hgq"/><path class="icz8l1jmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:notebook-pen-20" /></template>
