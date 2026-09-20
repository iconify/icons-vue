<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmllns1vc.css';
import '../../css/u/uqy1x4y0w.css';
import '../../css/d/d1kn0uj4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmllns1vc"/><path class="uqy1x4y0w"/><path class="d1kn0uj4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scraparr" /></template>
