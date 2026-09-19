<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w480wccdv.css';
import '../../css/k/kgvfx3eho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w480wccdv"/><path class="kgvfx3eho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:medal" /></template>
