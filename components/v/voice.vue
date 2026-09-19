<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq146_btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq146_btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:voice" /></template>
