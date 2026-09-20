<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lknj651ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lknj651ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zap-sharp-duotone" /></template>
