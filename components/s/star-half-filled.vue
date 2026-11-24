<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9vg974e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9vg974e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-half-filled" /></template>
