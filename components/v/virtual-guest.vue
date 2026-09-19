<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sunnwjbfh.css';
import '../../css/s/sn5sf53te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sunnwjbfh"/><path class="sn5sf53te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:virtual-guest" /></template>
