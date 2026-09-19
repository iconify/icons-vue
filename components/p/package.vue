<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc9l-bcsn.css';
import '../../css/b/b16rfrbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc9l-bcsn"/><path class="b16rfrbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:package" /></template>
