<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nkpbl8y9v.css';
import '../../css/m/mio52ig2b.css';
import '../../css/e/ez1x61b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nkpbl8y9v"/><circle class="mio52ig2b"/><circle class="ez1x61b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-cog-2" /></template>
