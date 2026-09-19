<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx_4fpbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="qx_4fpbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:test-bottle" /></template>
