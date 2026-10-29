<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b88urv4zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b88urv4zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:menu-solid" /></template>
