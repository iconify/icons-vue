<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guacuabyw.css';
import '../../css/w/wqgx4hy9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guacuabyw"/><path class="wqgx4hy9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:open-door-line" /></template>
