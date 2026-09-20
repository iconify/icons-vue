<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha9b68b0m.css';
import '../../css/f/fjxvhi0bo.css';
import '../../css/f/ftf34c06p.css';
import '../../css/l/l2ptp5l2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ha9b68b0m"/><path clip-rule="evenodd" class="fjxvhi0bo"/><path class="ftf34c06p"/><path clip-rule="evenodd" class="l2ptp5l2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nintendo-switch-solid" /></template>
