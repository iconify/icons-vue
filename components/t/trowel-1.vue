<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4hkoobwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="e4hkoobwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:trowel-1" /></template>
