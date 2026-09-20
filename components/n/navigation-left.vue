<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owp42ei7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owp42ei7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:navigation-left" /></template>
