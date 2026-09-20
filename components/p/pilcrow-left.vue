<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc2o02nwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc2o02nwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pilcrow-left" /></template>
