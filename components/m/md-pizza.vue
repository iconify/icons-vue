<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asrsfxb5s.css';
import '../../css/m/mepmou5ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asrsfxb5s"/><path class="mepmou5ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-pizza" /></template>
