<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd96l610s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kd96l610s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:unlock-16" /></template>
