<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx_bzmb5r.css';
import '../../css/w/wg9upwoxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_bzmb5r"/><path clip-rule="evenodd" class="wg9upwoxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:shakers-24" /></template>
