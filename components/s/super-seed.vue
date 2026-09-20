<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssdxi2bok.css';
import '../../css/b/b2qgwseyp.css';
import '../../css/l/lqp4slntg.css';
import '../../css/a/a9osemp6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssdxi2bok"/><path class="b2qgwseyp"/><path class="lqp4slntg"/><path clip-rule="evenodd" class="a9osemp6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:super-seed" /></template>
