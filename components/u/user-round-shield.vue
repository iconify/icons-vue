<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plpgm1gvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plpgm1gvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-round-shield" /></template>
