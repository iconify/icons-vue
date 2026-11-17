<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/b/bw2e53iyy.css';
import '../../css/m/mnowo9bkj.css';
import '../../css/v/v1--xxbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="bw2e53iyy"/><path class="mnowo9bkj"/><path class="v1--xxbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:octagon-x" /></template>
