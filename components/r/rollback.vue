<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lby_fq87n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lby_fq87n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rollback" /></template>
