<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv3y_4b2h.css';
import '../../css/r/rhaxarb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qv3y_4b2h"/><path class="rhaxarb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysblackdownpointingindex" /></template>
