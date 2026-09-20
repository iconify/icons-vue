<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xli4t7b_v.css';
import '../../css/d/dwyzddbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xli4t7b_v"/><path class="dwyzddbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:transfer-peso" /></template>
