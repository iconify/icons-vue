<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgy4m7b3h.css';
import '../../css/j/jr6hdmxwt.css';
import '../../css/g/gk5djfwmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mgy4m7b3h"/><path clip-rule="evenodd" class="jr6hdmxwt"/><path class="gk5djfwmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:notebook-duotone" /></template>
