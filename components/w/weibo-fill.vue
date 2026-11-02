<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdoiq_qel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdoiq_qel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weibo-fill" /></template>
