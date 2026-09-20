<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh09se2-w.css';
import '../../css/d/d-u2lgcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bh09se2-w"/><path class="d-u2lgcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:padding" /></template>
