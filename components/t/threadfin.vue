<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5mzdhlgm.css';
import '../../css/w/wjafqsbeh.css';
import '../../css/s/s9be24r1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5mzdhlgm"/><path class="wjafqsbeh"/><path class="s9be24r1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threadfin" /></template>
