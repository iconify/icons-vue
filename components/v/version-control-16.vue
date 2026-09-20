<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-dpuslot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c-dpuslot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:version-control-16" /></template>
