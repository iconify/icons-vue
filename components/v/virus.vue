<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbj8zt_ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbj8zt_ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:virus" /></template>
