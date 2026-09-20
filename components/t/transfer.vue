<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldbtn_0ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldbtn_0ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transfer" /></template>
