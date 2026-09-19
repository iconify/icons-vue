<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cn7oi9-ou.css';
import '../../css/c/cjcuh_i5u.css';
import '../../css/f/fsshfvbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cn7oi9-ou"/><circle transform="rotate(-180 11 11)" class="cjcuh_i5u"/><path class="fsshfvbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:pen-thin" /></template>
