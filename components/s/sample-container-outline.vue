<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txbq1dqrx.css';
import '../../css/s/ss55p0bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txbq1dqrx"/><path clip-rule="evenodd" class="ss55p0bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:sample-container-outline" /></template>
