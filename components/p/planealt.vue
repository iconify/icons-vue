<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxbx1y43n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="nxbx1y43n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:planealt" /></template>
