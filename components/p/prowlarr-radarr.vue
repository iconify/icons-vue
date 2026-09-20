<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-wkamaxf.css';
import '../../css/b/bsm7zc0tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="bsm7zc0tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prowlarr-radarr" /></template>
