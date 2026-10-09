<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bygov5bnk.css';
import '../../css/c/cgej8yb_k.css';
import '../../css/b/b6r2r-z2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bygov5bnk"/><path class="cgej8yb_k"/><path class="b6r2r-z2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-bolt-20" /></template>
