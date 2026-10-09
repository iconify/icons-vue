<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/non8y593o.css';
import '../../css/b/bbclq6bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="non8y593o"/><path class="bbclq6bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mouse-20" /></template>
