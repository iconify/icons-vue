<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox5bagm_m.css';
import '../../css/a/a-uqmqb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5bagm_m"/><path class="a-uqmqb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medical-kit" /></template>
