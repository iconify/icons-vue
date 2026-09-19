<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkbdgob_u.css';
import '../../css/b/ba4pmswhb.css';
import '../../css/k/kvokd1fvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkbdgob_u"/><path class="ba4pmswhb"/><path class="kvokd1fvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speaker3soundwaves" /></template>
