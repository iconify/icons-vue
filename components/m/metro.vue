<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_vz1bhc.css';
import '../../css/z/zgk5_n2-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="ac_vz1bhc"/><path class="zgk5_n2-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:metro" /></template>
