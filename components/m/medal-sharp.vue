<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjy_8-bky.css';
import '../../css/y/yehn7qb3c.css';
import '../../css/x/xfs19bcvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjy_8-bky"/><path class="yehn7qb3c"/><circle class="xfs19bcvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:medal-sharp" /></template>
