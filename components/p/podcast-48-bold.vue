<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdk3tib5a.css';
import '../../css/s/s61-nmb9n.css';
import '../../css/o/ozbsdeb5e.css';
import '../../css/u/up_jo7btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vdk3tib5a"/><path class="s61-nmb9n"/><path class="ozbsdeb5e"/><path class="up_jo7btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:podcast-48-bold" /></template>
