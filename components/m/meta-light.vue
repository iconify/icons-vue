<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fup5lsbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fup5lsbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meta-light" /></template>
