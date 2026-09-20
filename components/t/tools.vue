<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbjjubn9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-1};
const content = `<path class="qbjjubn9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tools" /></template>
