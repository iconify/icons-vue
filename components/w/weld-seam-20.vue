<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea2kc5baq.css';
import '../../css/o/obkbes3ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ea2kc5baq"/><path class="obkbes3ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weld-seam-20" /></template>
