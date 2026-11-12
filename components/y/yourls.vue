<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-ci9buu.css';
import '../../css/p/pg2petbgm.css';
import '../../css/e/ewxgxm6jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq-ci9buu"/><path class="pg2petbgm"/><path class="ewxgxm6jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yourls" /></template>
