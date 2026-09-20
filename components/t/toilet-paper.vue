<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyn1bjb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyn1bjb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:toilet-paper" /></template>
