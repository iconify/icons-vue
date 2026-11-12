<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh1d8hbja.css';
import '../../css/p/p6gi491tx.css';
import '../../css/b/bk36q5c0k.css';
import '../../css/a/alcx3ebvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wh1d8hbja"/><path class="p6gi491tx"/><path class="bk36q5c0k"/><path class="alcx3ebvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sando-dark" /></template>
