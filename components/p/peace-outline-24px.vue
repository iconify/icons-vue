<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9m7r_x7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9m7r_x7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:peace-outline-24px" /></template>
