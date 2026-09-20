<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmh04e.css';
import '../../css/m/m7jivk.css';
import '../../css/d/d-h_4q1i.css';
import '../../css/d/d-p1bg5r.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-cqmtvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmh04e"/><circle class="m7jivk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:watch-loop" /></template>
