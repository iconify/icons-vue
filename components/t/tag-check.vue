<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-5jx4blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-5jx4blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-check" /></template>
