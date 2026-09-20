<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-55t6b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="b-55t6b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-linear" /></template>
