<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvu2p6bej.css';
import '../../css/v/v_h7thdam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvu2p6bej"/><path class="v_h7thdam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perfice-light" /></template>
