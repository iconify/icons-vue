<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjq2w1_ae.css';
import '../../css/n/nbgk0wbrq.css';
import '../../css/d/dj35aibbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjq2w1_ae"/><path class="nbgk0wbrq"/><path class="dj35aibbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:people-nearby-bold-duotone" /></template>
