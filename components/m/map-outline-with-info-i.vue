<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdxfm_-fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bdxfm_-fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-outline-with-info-i" /></template>
