<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypditfboi.css';
import '../../css/j/j2j3gdcfi.css';
import '../../css/x/xxphl5biz.css';
import '../../css/y/yo5mywban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypditfboi"/><path class="j2j3gdcfi"/><path class="xxphl5biz"/><path class="yo5mywban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mouse" /></template>
