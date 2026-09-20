<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvdaepbqt.css';
import '../../css/y/y1wes1v3b.css';
import '../../css/v/v9dfp9b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qvdaepbqt"/><path class="y1wes1v3b"/><path class="v9dfp9b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onlyoffice" /></template>
