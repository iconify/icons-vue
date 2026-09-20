<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpsyw0ehr.css';
import '../../css/i/io_v3whei.css';
import '../../css/s/sn4d4xbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpsyw0ehr"/><path class="io_v3whei"/><path class="sn4d4xbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whodb-dark" /></template>
