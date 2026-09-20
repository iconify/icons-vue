<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1-5a6jdl.css';
import '../../css/j/jj_zol4wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1-5a6jdl"/><path class="jj_zol4wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:tilgjengelighet-lydtekst" /></template>
