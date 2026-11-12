<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21fiubni.css';
import '../../css/l/lxxu1wx1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m21fiubni"/><path class="lxxu1wx1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pufferpanel" /></template>
