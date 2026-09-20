<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd6if1b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qd6if1b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-1-filled" /></template>
