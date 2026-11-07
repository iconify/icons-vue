<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxlgg64z.css';
import '../../css/p/pwgp6wb0l.css';
import '../../css/g/gw5xq8brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="pwgp6wb0l"/><path class="gw5xq8brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-circle-bold-duotone" /></template>
