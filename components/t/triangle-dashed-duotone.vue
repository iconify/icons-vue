<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0e2h4bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z0e2h4bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-dashed-duotone" /></template>
