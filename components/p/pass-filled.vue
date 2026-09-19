<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-bnw_0yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-bnw_0yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pass-filled" /></template>
