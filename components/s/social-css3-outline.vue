<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixdm9acjc.css';
import '../../css/i/irl9z8uwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixdm9acjc"/><path class="irl9z8uwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-css3-outline" /></template>
