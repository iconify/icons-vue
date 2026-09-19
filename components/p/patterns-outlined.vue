<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tju-24idz.css';
import '../../css/l/lxi39ds5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tju-24idz"/><path class="lxi39ds5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:patterns-outlined" /></template>
