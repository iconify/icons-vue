<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgl48qxhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgl48qxhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:symfony" /></template>
