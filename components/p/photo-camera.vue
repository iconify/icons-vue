<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muz8hiwra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="muz8hiwra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:photo-camera" /></template>
