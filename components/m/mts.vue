<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxgf4qeum.css';
import '../../css/c/c_ewb9bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxgf4qeum"/><path class="c_ewb9bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mts" /></template>
