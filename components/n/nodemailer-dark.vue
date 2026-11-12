<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cspl7mbgk.css';
import '../../css/r/rq1b_prvq.css';
import '../../css/v/vydu3dknt.css';
import '../../css/i/i-6i6abaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cspl7mbgk"/><path class="rq1b_prvq"/><path class="vydu3dknt"/><path class="i-6i6abaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodemailer-dark" /></template>
