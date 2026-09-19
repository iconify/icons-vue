<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bosx53r-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bosx53r-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:razor-blade" /></template>
