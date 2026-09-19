<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx9lqb31c.css';
import '../../css/i/isdp0_b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx9lqb31c"/><path clip-rule="evenodd" class="isdp0_b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:stats-alt-2" /></template>
