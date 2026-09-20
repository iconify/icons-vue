<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj0391bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj0391bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ship" /></template>
