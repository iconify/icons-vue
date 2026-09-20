<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv-d8hb5y.css';
import '../../css/o/o-uubwh4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hv-d8hb5y"/><path clip-rule="evenodd" class="o-uubwh4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:unknown-16" /></template>
