<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk_6gseuv.css';
import '../../css/j/jtop0ctzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk_6gseuv"/><path class="jtop0ctzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:user-headset-solid" /></template>
