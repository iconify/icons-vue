<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn5cfnlkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn5cfnlkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pound-send" /></template>
