<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pme5qfb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pme5qfb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-directory" /></template>
