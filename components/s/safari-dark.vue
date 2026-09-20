<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8gv7plen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8gv7plen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:safari-dark" /></template>
