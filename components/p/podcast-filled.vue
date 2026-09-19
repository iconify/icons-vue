<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzhc1vhit.css';
import '../../css/f/fiyyqmf7i.css';
import '../../css/u/uuvohyb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzhc1vhit"/><path clip-rule="evenodd" class="fiyyqmf7i"/><path clip-rule="evenodd" class="uuvohyb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:podcast-filled" /></template>
