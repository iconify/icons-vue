<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azy1lpbdu.css';
import '../../css/x/xwsg8i03s.css';
import '../../css/k/knfcb1bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azy1lpbdu"/><path class="xwsg8i03s"/><path class="knfcb1bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-bold-duotone" /></template>
