<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jerixg-mq.css';
import '../../css/x/x-sfqoban.css';
import '../../css/d/d46zpdbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jerixg-mq"/><path class="x-sfqoban"/><path class="d46zpdbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-defender-dark" /></template>
