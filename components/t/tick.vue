<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvz35lkgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvz35lkgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:tick" /></template>
