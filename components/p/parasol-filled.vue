<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgqp7bbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgqp7bbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:parasol-filled" /></template>
