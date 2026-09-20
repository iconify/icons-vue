<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg5l84btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5l84btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nextdns" /></template>
