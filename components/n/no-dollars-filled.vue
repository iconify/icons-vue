<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb1h9rbig.css';
import '../../css/d/dglb7bs3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1h9rbig"/><path class="dglb7bs3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:no-dollars-filled" /></template>
