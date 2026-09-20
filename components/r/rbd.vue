<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh9iygkio.css';
import '../../css/n/ncs9kybml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9iygkio"/><path class="ncs9kybml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rbd" /></template>
