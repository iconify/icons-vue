<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gwgplcc3u.css';
import '../../css/g/gp0egaclj.css';
import '../../css/b/bopi9b9jn.css';
import '../../css/f/fxwnb7vgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwgplcc3u"/><circle class="gp0egaclj"/><circle class="bopi9b9jn"/><circle class="fxwnb7vgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:orbit" /></template>
