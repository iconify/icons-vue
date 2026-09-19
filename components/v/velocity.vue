<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvj7pvbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":457,"height":512};
const content = `<path class="mvj7pvbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:velocity" /></template>
