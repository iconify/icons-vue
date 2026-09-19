<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j432o5vub.css';
import '../../css/i/i5ssqcpbz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 j432o5vub"/><rect class="clr-i-solid clr-i-solid-path-2 i5ssqcpbz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:step-forward-solid" /></template>
