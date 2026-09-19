<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pck6pgbpl.css';
import '../../css/v/vh5zprbhd.css';
import '../../css/n/nf8po2uuu.css';
import '../../css/x/x2bo9tb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pck6pgbpl"/><path class="vh5zprbhd"/><path class="nf8po2uuu"/><path class="x2bo9tb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:switcher-twotone" /></template>
