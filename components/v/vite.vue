<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v89hnb0kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":510,"height":512};
const content = `<path class="v89hnb0kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vite" /></template>
