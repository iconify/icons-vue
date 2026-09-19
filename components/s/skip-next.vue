<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdrf14ebl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdrf14ebl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skip-next" /></template>
