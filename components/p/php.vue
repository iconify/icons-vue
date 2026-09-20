<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9hy3cbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9hy3cbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:php" /></template>
