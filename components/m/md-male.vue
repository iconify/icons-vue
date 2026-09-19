<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quhl277kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="quhl277kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-male" /></template>
