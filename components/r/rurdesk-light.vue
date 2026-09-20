<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj9owmbzf.css';
import '../../css/a/a-4ue5bby.css';
import '../../css/u/u0kmufbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj9owmbzf"/><path class="a-4ue5bby"/><circle class="u0kmufbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rurdesk-light" /></template>
