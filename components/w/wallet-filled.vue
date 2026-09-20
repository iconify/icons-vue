<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t51t1vv5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t51t1vv5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wallet-filled" /></template>
