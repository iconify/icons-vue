<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzv_u_b-g.css';
import '../../css/n/noehlf0bk.css';
import '../../css/f/fk0yjerem.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nzv_u_b-g"/><circle class="noehlf0bk"/><path class="fk0yjerem"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:thin-client-line" /></template>
