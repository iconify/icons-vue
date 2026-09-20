<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sld39kbbp.css';
import '../../css/o/o4c4j_blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sld39kbbp"/><path class="o4c4j_blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sidebar-expand-16" /></template>
