<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7kd-cczz.css';
import '../../css/l/lvinadbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7kd-cczz"/><path class="lvinadbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-rewind-duotone" /></template>
