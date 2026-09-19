<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lis884bqb.css';
import '../../css/j/jp1mmybuc.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 lis884bqb"/><path class="clr-i-solid clr-i-solid-path-1 jp1mmybuc"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tags-solid" /></template>
