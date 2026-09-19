<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnzt_ubit.css';
import '../../css/c/c435is_7m.css';
import '../../css/m/m42cvdv3o.css';
import '../../css/f/f18qcjqug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnzt_ubit"/><path class="c435is_7m"/><path class="m42cvdv3o"/><circle class="f18qcjqug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:microscope" /></template>
