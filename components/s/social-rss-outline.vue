<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm38_v6rc.css';
import '../../css/v/vvnu2369n.css';
import '../../css/b/bwfceobyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mm38_v6rc"/><path class="vvnu2369n"/><path class="bwfceobyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-rss-outline" /></template>
