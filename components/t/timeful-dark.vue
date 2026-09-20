<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtx7r_b3k.css';
import '../../css/l/ln1vkxyeu.css';
import '../../css/k/knqmx4bzv.css';
import '../../css/t/th2rkvb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mtx7r_b3k"/><path class="ln1vkxyeu"/><path class="knqmx4bzv"/><path class="th2rkvb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:timeful-dark" /></template>
