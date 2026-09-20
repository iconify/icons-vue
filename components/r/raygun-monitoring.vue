<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifwegobae.css';
import '../../css/b/bi8laefud.css';
import '../../css/y/yj-_c0bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifwegobae"/><path class="bi8laefud"/><path class="yj-_c0bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raygun-monitoring" /></template>
