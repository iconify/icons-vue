<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rutj5objf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rutj5objf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spacebar-filled" /></template>
