<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at1_iwbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at1_iwbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:volume-down" /></template>
