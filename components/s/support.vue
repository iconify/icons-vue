<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/audo1xb5t.css';
import '../../css/v/vbbpf97ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="audo1xb5t"/><path class="vbbpf97ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:support" /></template>
