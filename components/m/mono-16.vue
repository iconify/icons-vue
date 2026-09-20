<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-53zh46y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x-53zh46y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mono-16" /></template>
