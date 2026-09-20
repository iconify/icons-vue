<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzmusacjq.css';
import '../../css/k/ks466_bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzmusacjq"/><path class="ks466_bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moov" /></template>
