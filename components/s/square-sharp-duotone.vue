<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkdotthhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkdotthhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-sharp-duotone" /></template>
