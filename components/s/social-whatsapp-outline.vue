<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9gk6b6yh.css';
import '../../css/v/vfp8vn0fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g9gk6b6yh"/><path class="vfp8vn0fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-whatsapp-outline" /></template>
