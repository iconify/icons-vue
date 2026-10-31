<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv0i5uk2c.css';
import '../../css/k/k1r99mbvw.css';
import '../../css/p/pt9o2mr1h.css';
import '../../css/i/inrxyjbem.css';
import '../../css/c/ckn517gcp.css';
import '../../css/k/knsr51bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="iv0i5uk2c"/><path class="k1r99mbvw"/><path class="pt9o2mr1h"/><path class="inrxyjbem"/><path class="ckn517gcp"/><path class="knsr51bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:rainbow" /></template>
