<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbkebpbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbkebpbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vanguard" /></template>
