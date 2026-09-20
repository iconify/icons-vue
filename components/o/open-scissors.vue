<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swrm6uh7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="swrm6uh7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-scissors" /></template>
