<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h--dx184e.css';
import '../../css/g/ghya2pbow.css';
import '../../css/n/ny1qr-80o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h--dx184e"/><circle class="ghya2pbow"/><circle class="ny1qr-80o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-key" /></template>
