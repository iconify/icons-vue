<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z43p-_bzo.css';
import '../../css/t/tq_cotbup.css';
import '../../css/b/b-tgazyav.css';
import '../../css/q/qp7vvacem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z43p-_bzo"/><path class="tq_cotbup"/><path class="b-tgazyav"/><path class="qp7vvacem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-bold-duotone" /></template>
