<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/botwy-b2l.css';
import '../../css/i/icimvxwqo.css';
import '../../css/j/j9bcembrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="botwy-b2l"/><path class="icimvxwqo"/><path class="j9bcembrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unimus-dark" /></template>
