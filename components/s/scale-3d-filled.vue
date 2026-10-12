<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6c6j0kyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6c6j0kyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scale-3d-filled" /></template>
