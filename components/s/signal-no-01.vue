<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hicz8ocee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hicz8ocee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-no-01" /></template>
