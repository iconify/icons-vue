<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0oe49b3b.css';
import '../../css/p/p4r4-2bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a0oe49b3b"/><path class="p4r4-2bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reminder-medical" /></template>
