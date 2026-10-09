<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvf62xf5g.css';
import '../../css/k/k-8tebcux.css';
import '../../css/g/gz2x7rbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vvf62xf5g"/><path class="k-8tebcux"/><path class="gz2x7rbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screw-20-bold" /></template>
