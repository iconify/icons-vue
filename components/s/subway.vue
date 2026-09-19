<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmhu_wbhm.css';
import '../../css/c/cfnmk50zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmhu_wbhm"/><path class="cfnmk50zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:subway" /></template>
