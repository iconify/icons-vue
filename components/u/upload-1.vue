<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkikw8e4q.css';
import '../../css/x/xmqhqyf1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="xkikw8e4q"/><path class="xmqhqyf1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:upload-1" /></template>
