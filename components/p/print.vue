<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi8fqqbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi8fqqbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:print" /></template>
