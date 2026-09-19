<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idhihzbba.css';
import '../../css/g/g3esovain.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="idhihzbba"/><path class="g3esovain"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-skip-forward" /></template>
