<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-ixdzbom.css';
import '../../css/f/ffofn9bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-ixdzbom"/><path class="ffofn9bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wave-period" /></template>
