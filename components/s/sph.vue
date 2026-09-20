<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpix9fb8w.css';
import '../../css/z/zv089qb6t.css';
import '../../css/q/qbpcbfb9m.css';
import '../../css/b/bgzb_wqcm.css';
import '../../css/q/ql-lm2bge.css';
import '../../css/a/avujeybwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpix9fb8w"/><path class="zv089qb6t"/><path class="qbpcbfb9m"/><path class="bgzb_wqcm"/><path class="ql-lm2bge"/><path class="avujeybwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sph" /></template>
