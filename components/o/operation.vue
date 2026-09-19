<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hblu1qb3f.css';
import '../../css/o/o-a8ss1od.css';
import '../../css/r/r2mg1wbgz.css';
import '../../css/g/gw0_bj--j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hblu1qb3f"/><path class="o-a8ss1od"/><path class="r2mg1wbgz"/><path class="gw0_bj--j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:operation" /></template>
