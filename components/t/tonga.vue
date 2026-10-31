<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zifxdrbtd.css';
import '../../css/t/tbr-k1iil.css';
import '../../css/l/lz56vjbyd.css';
import '../../css/p/pzi5q3boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="zifxdrbtd"/><path class="tbr-k1iil"/><path class="lz56vjbyd"/><path class="pzi5q3boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:tonga" /></template>
