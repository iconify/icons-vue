<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqz7ptbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rqz7ptbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sausage" /></template>
