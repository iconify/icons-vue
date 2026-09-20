<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsic9tbse.css';
import '../../css/f/fr9wnwjpk.css';
import '../../css/c/c6vuqnbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsic9tbse"/><path class="fr9wnwjpk"/><path class="c6vuqnbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:re-director" /></template>
