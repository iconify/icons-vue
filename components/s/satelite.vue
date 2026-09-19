<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7t30-klj.css';
import '../../css/n/nbg7fqb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s7t30-klj"/><path class="nbg7fqb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:satelite" /></template>
