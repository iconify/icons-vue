<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9vcwpudw.css';
import '../../css/b/b5b9_cc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="v9vcwpudw"/><circle class="b5b9_cc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimerobot" /></template>
