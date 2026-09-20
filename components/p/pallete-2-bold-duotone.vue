<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt5ganbfh.css';
import '../../css/t/tqowt8nqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt5ganbfh"/><path class="tqowt8nqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pallete-2-bold-duotone" /></template>
