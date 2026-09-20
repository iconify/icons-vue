<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq2o04i_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gq2o04i_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-mask-remix" /></template>
