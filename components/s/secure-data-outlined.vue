<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5kv5b4d.css';
import '../../css/h/hd-ff83io.css';
import '../../css/z/zq_37wb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci5kv5b4d"/><path class="hd-ff83io"/><path class="zq_37wb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:secure-data-outlined" /></template>
