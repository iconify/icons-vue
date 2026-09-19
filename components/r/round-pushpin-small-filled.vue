<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_fpo-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c_fpo-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:round-pushpin-small-filled" /></template>
