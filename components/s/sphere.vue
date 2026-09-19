<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y9ra9v_nc.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/m/mt1kbjbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y9ra9v_nc"/><circle class="shu3xdl9q"/><path class="mt1kbjbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sphere" /></template>
