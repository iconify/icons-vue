<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yavxk_bsz.css';
import '../../css/i/ixpy7yyki.css';
import '../../css/p/pn-hlnbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yavxk_bsz"/><path class="ixpy7yyki"/><path class="pn-hlnbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:profile" /></template>
