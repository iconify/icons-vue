<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic98o8bay.css';
import '../../css/w/wprsklb5k.css';
import '../../css/o/owe3-0brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ic98o8bay"/><path class="wprsklb5k"/><path class="owe3-0brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:russia" /></template>
