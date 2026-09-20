<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0kn04bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0kn04bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-minus" /></template>
