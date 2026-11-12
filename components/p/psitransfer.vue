<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpt1a073y.css';
import '../../css/z/zbfwn0b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kpt1a073y"/><path class="zbfwn0b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:psitransfer" /></template>
