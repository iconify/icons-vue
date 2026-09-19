<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq33zac2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qq33zac2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vertical-view" /></template>
