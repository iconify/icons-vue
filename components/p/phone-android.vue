<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5t4xbsr.css';
import '../../css/w/w2xstcbue.css';
import '../../css/r/rq_3jfb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc5t4xbsr"/><path class="w2xstcbue"/><path class="rq_3jfb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:phone-android" /></template>
