<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw7d88cbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw7d88cbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:record-mail-off" /></template>
