<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvm2ckb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvm2ckb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrutiny-light" /></template>
