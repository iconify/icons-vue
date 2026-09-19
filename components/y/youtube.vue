<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgsnhxbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":432};
const content = `<path class="sgsnhxbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:youtube" /></template>
