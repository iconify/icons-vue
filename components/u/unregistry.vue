<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bltugjkhs.css';
import '../../css/v/vq3qgrprl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bltugjkhs"/><path class="vq3qgrprl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unregistry" /></template>
