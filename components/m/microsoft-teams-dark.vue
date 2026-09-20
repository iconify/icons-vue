<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggt1geb1l.css';
import '../../css/x/xr2facclf.css';
import '../../css/a/atnwqg8za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggt1geb1l"/><path class="xr2facclf"/><path class="atnwqg8za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-teams-dark" /></template>
