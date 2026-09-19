<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1e1ldbxe.css';
import '../../css/b/beggmnimb.css';
import '../../css/p/psrn3dbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1e1ldbxe"/><path class="beggmnimb"/><path class="psrn3dbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:story" /></template>
