<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxqgy5otv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxqgy5otv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:upload" /></template>
