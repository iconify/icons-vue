<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz50wxbre.css';
import '../../css/z/zh9lxxd8p.css';
import '../../css/j/jzsn4fblp.css';
import '../../css/a/a5nz24eur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pz50wxbre"/><path class="zh9lxxd8p"/><path class="jzsn4fblp"/><path class="a5nz24eur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbackbone" /></template>
