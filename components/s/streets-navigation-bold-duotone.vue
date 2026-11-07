<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa4c_mbug.css';
import '../../css/o/o98yw8b4w.css';
import '../../css/x/xt-xue_6i.css';
import '../../css/k/kric1lb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4c_mbug"/><path class="o98yw8b4w"/><path class="xt-xue_6i"/><path class="kric1lb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-bold-duotone" /></template>
