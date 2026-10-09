<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-02z6b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-02z6b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pause-20" /></template>
