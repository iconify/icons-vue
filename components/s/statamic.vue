<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2686umpn.css';
import '../../css/v/v4ezc_mia.css';
import '../../css/y/ycs9ylboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2686umpn"/><path class="v4ezc_mia"/><path class="ycs9ylboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:statamic" /></template>
