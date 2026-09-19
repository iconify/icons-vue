<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo49c-7rn.css';
import '../../css/e/ev1e0nbdz.css';
import '../../css/y/yiwzwpb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo49c-7rn"/><path class="ev1e0nbdz"/><path class="yiwzwpb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:speak" /></template>
