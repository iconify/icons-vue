<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2qwjtp6x.css';
import '../../css/n/n3zvsabum.css';
import '../../css/l/l3c5_9blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qwjtp6x"/><path class="n3zvsabum"/><path class="l3c5_9blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:snx" /></template>
