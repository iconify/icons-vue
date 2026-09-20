<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmx9skinh.css';
import '../../css/x/xc4hi7hnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmx9skinh"/><path class="xc4hi7hnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-grumpy" /></template>
