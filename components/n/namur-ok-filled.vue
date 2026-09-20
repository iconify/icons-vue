<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqj-w3bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqj-w3bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-ok-filled" /></template>
