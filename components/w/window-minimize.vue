<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxtrb1b8k.css';
import '../../css/h/ho146fqck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxtrb1b8k"/><path class="ho146fqck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:window-minimize" /></template>
