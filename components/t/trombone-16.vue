<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv_s9x15n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gv_s9x15n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trombone-16" /></template>
