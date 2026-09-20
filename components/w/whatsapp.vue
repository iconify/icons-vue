<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gk04yo4uu.css';
import '../../css/w/w7ieg6b4v.css';
import '../../css/r/rc8h5_bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="gk04yo4uu"/><circle class="w7ieg6b4v"/><path class="rc8h5_bqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:whatsapp" /></template>
