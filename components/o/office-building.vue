<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-pk2evut.css';
import '../../css/m/mxwo3o_cb.css';
import '../../css/v/v01vscs4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i-pk2evut"/><path class="mxwo3o_cb"/><path class="v01vscs4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:office-building" /></template>
