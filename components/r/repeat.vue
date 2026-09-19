<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb9o4qvoo.css';
import '../../css/z/zfvyp8bow.css';
import '../../css/d/dw4cdfjco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb9o4qvoo"/><path class="zfvyp8bow"/><path class="dw4cdfjco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:repeat" /></template>
