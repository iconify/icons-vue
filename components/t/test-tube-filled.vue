<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bapy_ccxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bapy_ccxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:test-tube-filled" /></template>
