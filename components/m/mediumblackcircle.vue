<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx919ebgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="qx919ebgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mediumblackcircle" /></template>
