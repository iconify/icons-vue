<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhhhswtjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhhhswtjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-increase-spacing" /></template>
