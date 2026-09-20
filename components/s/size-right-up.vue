<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d7r3h4bal.css';
import '../../css/n/nph80ib2c.css';
import '../../css/e/e_n9wrbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d7r3h4bal"/><path class="nph80ib2c"/><rect class="e_n9wrbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:size-right-up" /></template>
