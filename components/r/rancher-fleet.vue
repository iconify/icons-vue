<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twfeyencb.css';
import '../../css/h/hnsdbi_4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twfeyencb"/><path class="hnsdbi_4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-fleet" /></template>
