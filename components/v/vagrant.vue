<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i96mgiblb.css';
import '../../css/u/uj6e1ab-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":140.625,"height":140.625};
const content = `<path class="i96mgiblb"/><path class="uj6e1ab-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vagrant" /></template>
