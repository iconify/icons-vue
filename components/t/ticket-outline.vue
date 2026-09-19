<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8t_6bcva.css';
import '../../css/q/q2cv_lb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8t_6bcva"/><path class="q2cv_lb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ticket-outline" /></template>
