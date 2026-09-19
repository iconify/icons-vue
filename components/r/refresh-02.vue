<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo0s_cctr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0s_cctr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:refresh-02" /></template>
