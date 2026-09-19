<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lis884bqb.css';
import '../../css/r/rqjikdywo.css';
import '../../css/b/b2d36xbqv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 lis884bqb"/><circle class="clr-i-outline clr-i-outline-path-2 rqjikdywo"/><path class="b2d36xbqv clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tags-line" /></template>
