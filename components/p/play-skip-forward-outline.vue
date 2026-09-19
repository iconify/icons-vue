<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijl3j-lgr.css';
import '../../css/n/ngun-rqzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ijl3j-lgr"/><path class="ngun-rqzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-skip-forward-outline" /></template>
