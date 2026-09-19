<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwqxb2ble.css';
import '../../css/d/dibzppbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qwqxb2ble"/><path class="dibzppbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vaadin-wordmark" /></template>
