<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6vm1lw4k.css';
import '../../css/w/w-a0529lf.css';
import '../../css/v/vfdh2_b_f.css';
import '../../css/o/o0lqhvmmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6vm1lw4k"/><path class="w-a0529lf"/><path class="vfdh2_b_f"/><circle class="o0lqhvmmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:man-outline" /></template>
