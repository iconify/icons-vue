<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsxw_objg.css';
import '../../css/w/w_fbcy7gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsxw_objg"/><path class="w_fbcy7gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:note-mark" /></template>
