<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w37h81bqn.css';
import '../../css/c/ccl9t3mye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w37h81bqn"/><path class="ccl9t3mye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:pie-chart-filled" /></template>
