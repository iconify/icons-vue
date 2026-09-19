<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pibf0kb_r.css';
import '../../css/x/xts2abbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pibf0kb_r"/><path class="xts2abbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scan-detail-filled" /></template>
