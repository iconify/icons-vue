<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac0esgq2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac0esgq2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:volume-off" /></template>
