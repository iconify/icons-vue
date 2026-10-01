<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvt0s3njn.css';
import '../../css/v/vmr_zhb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvt0s3njn"/><path class="vmr_zhb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rabbit" /></template>
