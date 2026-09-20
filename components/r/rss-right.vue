<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sacl49i0j.css';
import '../../css/f/fv1pvlf1q.css';
import '../../css/q/qi3bd4p2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="sacl49i0j"/><path class="fv1pvlf1q"/><path class="qi3bd4p2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:rss-right" /></template>
