<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jupwx4haq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jupwx4haq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:xing" /></template>
