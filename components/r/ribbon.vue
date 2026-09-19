<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt8_63gik.css';
import '../../css/a/a2pc2urid.css';
import '../../css/q/qkkblme1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt8_63gik"/><ellipse class="a2pc2urid"/><path class="qkkblme1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ribbon" /></template>
