<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1268k_zf.css';
import '../../css/y/ypft5mbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1268k_zf"/><path class="ypft5mbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-locked-fill" /></template>
