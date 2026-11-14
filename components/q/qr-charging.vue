<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/uk6nrckuy.css';
import '../../css/q/qljskglob.css';
import '../../css/b/bqcg8gbob.css';
import '../../css/z/zwsam6e5w.css';
import '../../css/l/l9ehr-4nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uk6nrckuy"/><rect class="qljskglob"/><rect class="bqcg8gbob"/><path class="zwsam6e5w"/><path class="l9ehr-4nc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:qr-charging" /></template>
