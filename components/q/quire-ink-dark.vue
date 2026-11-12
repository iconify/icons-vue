<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5p876b5i.css';
import '../../css/v/vwv3t9bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5p876b5i"/><path class="vwv3t9bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quire-ink-dark" /></template>
