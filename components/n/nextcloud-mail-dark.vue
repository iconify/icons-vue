<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm9_89bsm.css';
import '../../css/z/z6-pcfb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xm9_89bsm"/><path class="z6-pcfb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-mail-dark" /></template>
