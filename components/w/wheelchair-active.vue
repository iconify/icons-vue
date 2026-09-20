<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzlc5jb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pzlc5jb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:wheelchair-active" /></template>
