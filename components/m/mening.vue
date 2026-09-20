<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfeh19hzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfeh19hzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:mening" /></template>
