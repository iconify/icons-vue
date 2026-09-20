<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8j5c3sho.css';
import '../../css/b/be5fe-z3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8j5c3sho"/><path class="be5fe-z3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:virtualbox-dark" /></template>
