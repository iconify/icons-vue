<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuq0axb2c.css';
import '../../css/u/uhazafbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="iuq0axb2c"/><circle class="uhazafbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimerobot-dark" /></template>
