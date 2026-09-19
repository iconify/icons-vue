<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gggi5_ica.css';
import '../../css/o/o_oa07brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gggi5_ica"/><path class="o_oa07brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-walk" /></template>
