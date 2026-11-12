<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl06gbc5c.css';
import '../../css/b/be5fe-z3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl06gbc5c"/><path class="be5fe-z3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:virtualbox-dark" /></template>
