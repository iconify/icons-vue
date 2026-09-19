<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izoaahe4v.css';
import '../../css/z/zrb4p4b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="izoaahe4v"/><path class="zrb4p4b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:notepage" /></template>
