<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rbqrvx45y.css';
import '../../css/m/mtuv6bbgk.css';
import '../../css/n/nbfqlubre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rbqrvx45y"/><path class="mtuv6bbgk"/><circle class="nbfqlubre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:profile-duotone" /></template>
