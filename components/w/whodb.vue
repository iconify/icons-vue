<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br-__gb2m.css';
import '../../css/a/a_399pbtf.css';
import '../../css/s/scjdmkghe.css';
import '../../css/h/h73mrwbie.css';
import '../../css/p/pgzmr_bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="br-__gb2m"/><path class="a_399pbtf"/><path class="scjdmkghe"/><path class="h73mrwbie"/><path class="pgzmr_bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whodb" /></template>
