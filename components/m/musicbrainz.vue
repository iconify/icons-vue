<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q25dr_b5z.css';
import '../../css/x/xoum1hbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q25dr_b5z"/><path class="xoum1hbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:musicbrainz" /></template>
