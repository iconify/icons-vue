<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx77dvllf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kx77dvllf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-check" /></template>
