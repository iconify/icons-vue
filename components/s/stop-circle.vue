<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5uore03m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5uore03m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:stop-circle" /></template>
