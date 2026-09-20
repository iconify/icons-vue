<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ae6vn1y.css';
import '../../css/h/h53yl6f8n.css';
import '../../css/j/jdgizublx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7ae6vn1y"/><path class="h53yl6f8n"/><path class="jdgizublx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nakama" /></template>
