<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjmdefyhd.css';
import '../../css/k/k4tc3yb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":277};
const content = `<path class="xjmdefyhd"/><path class="k4tc3yb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:redwoodjs" /></template>
