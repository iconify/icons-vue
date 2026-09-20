<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s4mc_pwhm.css';
import '../../css/f/f__d2e_ze.css';
import '../../css/u/urwd-umbj.css';
import '../../css/v/vrue9i-7y.css';
import '../../css/p/pcjed1bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s4mc_pwhm"/><path class="f__d2e_ze"/><path class="urwd-umbj"/><path class="vrue9i-7y"/><path class="pcjed1bar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mobilephone-action-location-lock" /></template>
