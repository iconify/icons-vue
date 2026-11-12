<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0bvlpdn.css';
import '../../css/t/tdr-0yasd.css';
import '../../css/s/s-edpzbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak0bvlpdn"/><path class="tdr-0yasd"/><path class="s-edpzbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synology" /></template>
