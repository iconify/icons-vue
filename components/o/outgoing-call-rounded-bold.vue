<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4_4mjb9l.css';
import '../../css/a/a8539c-uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4_4mjb9l"/><path class="a8539c-uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-rounded-bold" /></template>
